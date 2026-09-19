<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oxm7xqbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxm7xqbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shield-alt" {...props}></Icon>
