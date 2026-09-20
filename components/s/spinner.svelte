<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3117v-uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="u3117v-uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:spinner" {...props}></Icon>
