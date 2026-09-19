<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_z6oabmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_z6oabmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:step-backward" {...props}></Icon>
