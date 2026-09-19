<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryrdczeve.css';
import '../../css/h/hsnx_9cta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ryrdczeve"/><path class="duoicon-primary-layer hsnx_9cta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:slideshow" {...props}></Icon>
