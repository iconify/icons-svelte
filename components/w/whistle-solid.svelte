<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/om6x17_2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="om6x17_2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:whistle-solid" {...props}></Icon>
