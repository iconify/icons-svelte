<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cizn9vlgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cizn9vlgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:turix" {...props}></Icon>
