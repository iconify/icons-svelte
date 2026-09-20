<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rihw6xbol.css';
import '../../css/e/epi033bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rihw6xbol"/><path class="epi033bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shopping-bag-duty-free-bold" {...props}></Icon>
