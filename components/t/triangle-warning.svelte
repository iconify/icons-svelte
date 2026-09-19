<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj15hgbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj15hgbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:triangle-warning" {...props}></Icon>
