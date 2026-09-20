<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpe008b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpe008b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:scan-search-sharp" {...props}></Icon>
