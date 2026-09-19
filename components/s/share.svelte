<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn63m2b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn63m2b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:share" {...props}></Icon>
