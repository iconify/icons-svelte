<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mf7kf2bdd.css';
import '../../css/k/kjn-z4brj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mf7kf2bdd"/><path class="kjn-z4brj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:star-plus-filled" {...props}></Icon>
