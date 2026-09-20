<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv2k8ptcj.css';
import '../../css/r/rm4r7y8ko.css';
import '../../css/f/fixn44brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hv2k8ptcj"/><path class="rm4r7y8ko"/><path class="fixn44brh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:vault" {...props}></Icon>
