<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in_f27l9g.css';
import '../../css/l/l-21abmhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="in_f27l9g secondary"/><path class="l-21abmhq primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:tooth-duo" {...props}></Icon>
