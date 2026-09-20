<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgcju0jts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kgcju0jts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:sorting" {...props}></Icon>
