<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf0xtbtqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":29,"height":24};
const content = `<path class="uf0xtbtqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:table-1" {...props}></Icon>
