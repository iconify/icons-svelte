<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-ay5zbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x-ay5zbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:top-arrow-to-top" {...props}></Icon>
