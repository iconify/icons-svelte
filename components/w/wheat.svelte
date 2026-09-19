<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yowz-bcyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yowz-bcyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:wheat" {...props}></Icon>
