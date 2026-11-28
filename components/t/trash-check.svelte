<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwzsr340v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwzsr340v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:trash-check" {...props}></Icon>
