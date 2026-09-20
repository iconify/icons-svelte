<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/odwxg8bki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="odwxg8bki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:star-half-right-o" {...props}></Icon>
