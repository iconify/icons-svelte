<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnictt5xz.css';
import '../../css/y/ykz2ipeqp.css';
import '../../css/r/r6ujjtbfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vnictt5xz"/><path class="ykz2ipeqp"/><path class="r6ujjtbfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:warning-alt-inverted-filled" {...props}></Icon>
