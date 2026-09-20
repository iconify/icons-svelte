<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npx1l6b-f.css';
import '../../css/c/cywx5ebns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="npx1l6b-f"/><path class="cywx5ebns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sign-out" {...props}></Icon>
