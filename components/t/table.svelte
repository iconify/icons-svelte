<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9wu_sbja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o9wu_sbja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:table" {...props}></Icon>
