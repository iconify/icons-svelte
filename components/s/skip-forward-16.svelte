<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo1r5ubvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yo1r5ubvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:skip-forward-16" {...props}></Icon>
