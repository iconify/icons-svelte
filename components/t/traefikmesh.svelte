<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sor50jj-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sor50jj-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:traefikmesh" {...props}></Icon>
