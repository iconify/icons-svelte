<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h1m_geb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="h1m_geb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:users-rays" {...props}></Icon>
