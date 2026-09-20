<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_t__4isx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="n_t__4isx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:tablet" {...props}></Icon>
