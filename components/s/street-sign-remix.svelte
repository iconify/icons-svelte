<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9x6irbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="g9x6irbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:street-sign-remix" {...props}></Icon>
