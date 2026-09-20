<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omt-n94-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="omt-n94-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:tablet-fill" {...props}></Icon>
