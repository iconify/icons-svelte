<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na6dr8byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="na6dr8byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surveyjs-light" {...props}></Icon>
