<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_ses9b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="t_ses9b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wrap-right-fill-12" {...props}></Icon>
