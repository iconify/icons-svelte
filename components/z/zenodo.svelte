<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_mfofbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_mfofbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:zenodo" {...props}></Icon>
