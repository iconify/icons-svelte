<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myhk15bsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myhk15bsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:thumbs-down-fill" {...props}></Icon>
