<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr-9dwl7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fr-9dwl7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:stock-remix" {...props}></Icon>
