<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1kiis7qb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1408,"height":1472};
const content = `<path class="f1kiis7qb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:user-boss" {...props}></Icon>
