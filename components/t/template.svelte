<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aienk9a9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="aienk9a9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:template" {...props}></Icon>
