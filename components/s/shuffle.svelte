<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe550s3qf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe550s3qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:shuffle" {...props}></Icon>
