<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d57sztm3t.css';
import '../../css/z/z5b9-nbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d57sztm3t"/><path class="z5b9-nbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-exclude" {...props}></Icon>
