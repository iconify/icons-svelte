<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0zpqxnly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u0zpqxnly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wallet-cards-fill" {...props}></Icon>
