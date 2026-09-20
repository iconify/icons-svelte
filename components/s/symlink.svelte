<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4ezuz1il.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q4ezuz1il"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:symlink" {...props}></Icon>
