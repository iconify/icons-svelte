<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/glue_d-so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glue_d-so"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:toolbox-round" {...props}></Icon>
