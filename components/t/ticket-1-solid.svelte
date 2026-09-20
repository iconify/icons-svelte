<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9yzpjbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="h9yzpjbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:ticket-1-solid" {...props}></Icon>
