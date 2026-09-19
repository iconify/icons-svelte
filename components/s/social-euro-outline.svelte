<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxem6hx9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oxem6hx9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:social-euro-outline" {...props}></Icon>
