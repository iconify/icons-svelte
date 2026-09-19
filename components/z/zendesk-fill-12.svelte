<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5yrbob0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="s5yrbob0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:zendesk-fill-12" {...props}></Icon>
