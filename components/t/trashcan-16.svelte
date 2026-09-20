<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mp27ucbkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mp27ucbkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:trashcan-16" {...props}></Icon>
