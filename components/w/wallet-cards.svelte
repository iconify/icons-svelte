<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjm_2bbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjm_2bbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:wallet-cards" {...props}></Icon>
