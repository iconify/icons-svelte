<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jimqm7bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jimqm7bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:square-letter-t" {...props}></Icon>
