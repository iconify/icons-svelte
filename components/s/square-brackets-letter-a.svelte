<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fra-0totj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fra-0totj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-brackets-letter-a" {...props}></Icon>
