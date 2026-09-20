<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1cz-gh7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f1cz-gh7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:table-outline" {...props}></Icon>
