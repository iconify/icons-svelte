<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngr0d5mwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngr0d5mwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:taxi" {...props}></Icon>
