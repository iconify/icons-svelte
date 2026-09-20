<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uii4qobww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="uii4qobww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:share" {...props}></Icon>
