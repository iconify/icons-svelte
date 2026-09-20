<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hirnc1viw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hirnc1viw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nonicons:variable-16" {...props}></Icon>
