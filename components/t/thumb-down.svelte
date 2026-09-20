<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ud64q60rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ud64q60rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:thumb-down" {...props}></Icon>
