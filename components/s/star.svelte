<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w485043ft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="w485043ft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:star" {...props}></Icon>
