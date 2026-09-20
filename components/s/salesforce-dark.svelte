<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu9hx0bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gu9hx0bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:salesforce-dark" {...props}></Icon>
