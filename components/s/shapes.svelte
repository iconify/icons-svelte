<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfaggn45q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfaggn45q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shapes" {...props}></Icon>
