<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wydnq0baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wydnq0baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:status-health" {...props}></Icon>
