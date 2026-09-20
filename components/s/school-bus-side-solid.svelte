<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4mz7cb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4mz7cb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:school-bus-side-solid" {...props}></Icon>
