<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu7embbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hu7embbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-forward-fill" {...props}></Icon>
