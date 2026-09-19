<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nl6qsfbub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="nl6qsfbub"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:teamcity-wordmark" {...props}></Icon>
