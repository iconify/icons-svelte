<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tixo1lber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tixo1lber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:t-shirt" {...props}></Icon>
