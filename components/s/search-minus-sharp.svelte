<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npd_bhh0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npd_bhh0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:search-minus-sharp" {...props}></Icon>
