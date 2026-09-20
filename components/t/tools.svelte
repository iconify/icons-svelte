<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0lidos6q.css';
import '../../css/f/fokf_m9cy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v0lidos6q"/><path class="fokf_m9cy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:tools" {...props}></Icon>
