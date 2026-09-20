<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eec93pb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eec93pb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:sign-out-alt" {...props}></Icon>
