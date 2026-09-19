<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmoxa_buc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmoxa_buc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:switch" {...props}></Icon>
