<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1-5a6jdl.css';
import '../../css/j/jj_zol4wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n1-5a6jdl"/><path class="jj_zol4wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:tilgjengelighet-lydtekst" {...props}></Icon>
