<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5pil4b6d.css';
import '../../css/v/v5wzyp5ut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o5pil4b6d"/><circle class="v5wzyp5ut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:view-alt-duotone" {...props}></Icon>
