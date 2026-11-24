<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v27uo2wcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v27uo2wcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:skip-forward" {...props}></Icon>
