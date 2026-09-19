<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqn01wbgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hqn01wbgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:up-right-2-short-arrow" {...props}></Icon>
