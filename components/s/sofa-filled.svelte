<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fffgk-bgb.css';
import '../../css/s/s88v5t7cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fffgk-bgb"/><path class="s88v5t7cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:sofa-filled" {...props}></Icon>
