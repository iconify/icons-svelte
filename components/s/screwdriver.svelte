<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fokf_m9cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fokf_m9cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:screwdriver" {...props}></Icon>
