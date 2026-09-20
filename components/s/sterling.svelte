<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a52nb_zbg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a52nb_zbg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:sterling" {...props}></Icon>
