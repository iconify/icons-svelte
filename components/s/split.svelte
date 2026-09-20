<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miu2v2oim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="miu2v2oim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:split" {...props}></Icon>
