<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acbz_02fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acbz_02fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:unsplash" {...props}></Icon>
