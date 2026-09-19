<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7xigcc8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="j7xigcc8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:security-26" {...props}></Icon>
