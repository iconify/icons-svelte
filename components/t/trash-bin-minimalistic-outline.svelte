<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rdlwsowkl.css';
import '../../css/f/fib6k6-vs.css';
import '../../css/u/u3cpgbbrn.css';
import '../../css/i/ii8sfybxo.css';
import '../../css/j/jks_y-bbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rdlwsowkl"/><path class="fib6k6-vs"/><path class="u3cpgbbrn"/><path class="ii8sfybxo"/><path class="jks_y-bbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:trash-bin-minimalistic-outline" {...props}></Icon>
