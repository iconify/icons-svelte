<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsc21xyjd.css';
import '../../css/j/j9dld7jrj.css';
import '../../css/i/ipo79vlap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fsc21xyjd"/><path class="j9dld7jrj"/><path class="ipo79vlap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:safe-20" {...props}></Icon>
