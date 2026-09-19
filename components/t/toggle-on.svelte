<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kg6z7owzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="kg6z7owzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:toggle-on" {...props}></Icon>
