<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_2f1pbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_2f1pbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zendesk" {...props}></Icon>
