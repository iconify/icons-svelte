<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kieyk5oou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kieyk5oou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:ticketmaster" {...props}></Icon>
