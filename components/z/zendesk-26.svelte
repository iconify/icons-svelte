<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnrbddcgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="lnrbddcgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:zendesk-26" {...props}></Icon>
