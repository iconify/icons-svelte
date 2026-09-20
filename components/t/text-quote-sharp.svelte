<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5ibfrbgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5ibfrbgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:text-quote-sharp" {...props}></Icon>
