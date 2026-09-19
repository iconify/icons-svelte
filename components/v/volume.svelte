<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug90t0lcu.css';
import '../../css/v/v783iab8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ug90t0lcu"/><circle class="v783iab8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:volume" {...props}></Icon>
