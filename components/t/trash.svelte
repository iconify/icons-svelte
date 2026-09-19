<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1rvblkqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="d1rvblkqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:trash" {...props}></Icon>
