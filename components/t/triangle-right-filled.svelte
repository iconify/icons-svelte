<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n3ptqkb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n3ptqkb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:triangle-right-filled" {...props}></Icon>
