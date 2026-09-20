<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkii_8o6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bkii_8o6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:tanuki-verified" {...props}></Icon>
