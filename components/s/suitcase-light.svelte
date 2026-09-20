<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cowd3yulo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cowd3yulo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:suitcase-light" {...props}></Icon>
