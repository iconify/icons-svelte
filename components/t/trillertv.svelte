<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huk-a7b3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huk-a7b3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:trillertv" {...props}></Icon>
