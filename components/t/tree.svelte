<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9-_hx82t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="w9-_hx82t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:tree" {...props}></Icon>
