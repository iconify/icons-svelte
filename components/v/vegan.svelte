<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9n9rckuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9n9rckuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:vegan" {...props}></Icon>
