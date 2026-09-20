<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lez7u-jzv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lez7u-jzv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:tenet" {...props}></Icon>
