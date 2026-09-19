<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/moedqhbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="moedqhbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:volume" {...props}></Icon>
