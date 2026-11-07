<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quqkdstdb.css';
import '../../css/a/a7qf29bcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quqkdstdb"/><path class="a7qf29bcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-alt-arrow-up-bold-duotone" {...props}></Icon>
