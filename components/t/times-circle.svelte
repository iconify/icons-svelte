<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5kd2n3_d.css';
import '../../css/c/cvqusacuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n5kd2n3_d"/><path class="cvqusacuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:times-circle" {...props}></Icon>
