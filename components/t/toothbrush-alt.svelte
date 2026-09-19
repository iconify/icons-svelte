<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6zw37b2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h6zw37b2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:toothbrush-alt" {...props}></Icon>
