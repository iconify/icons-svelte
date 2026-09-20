<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwk3xhbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pwk3xhbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-letter-q-filled" {...props}></Icon>
