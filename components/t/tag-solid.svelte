<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocj-akbzq.css';
import '../../css/u/ug5oqdb4t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ocj-akbzq"/><path clip-rule="evenodd" class="ug5oqdb4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:tag-solid" {...props}></Icon>
