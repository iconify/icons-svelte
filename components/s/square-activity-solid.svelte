<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsuxle7aj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zsuxle7aj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:square-activity-solid" {...props}></Icon>
