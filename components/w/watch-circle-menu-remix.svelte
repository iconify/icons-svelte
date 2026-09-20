<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td2jlvbim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="td2jlvbim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:watch-circle-menu-remix" {...props}></Icon>
