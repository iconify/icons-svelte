<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pew7ey2cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pew7ey2cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:sign-division-circle-fill" {...props}></Icon>
