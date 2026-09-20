<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_s4tsbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="a_s4tsbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:smile" {...props}></Icon>
