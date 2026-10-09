<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7u15acll.css';
import '../../css/g/gl6s0rb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u7u15acll"/><path class="gl6s0rb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:toggle-left-20" {...props}></Icon>
