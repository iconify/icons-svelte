<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igfdo3bys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igfdo3bys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:shield-outline" {...props}></Icon>
