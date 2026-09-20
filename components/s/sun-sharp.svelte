<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqt7x9bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqt7x9bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sun-sharp" {...props}></Icon>
