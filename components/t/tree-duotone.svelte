<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gr70o2bnl.css';
import '../../css/n/nqu-0evvj.css';
import '../../css/k/kqeot6bhn.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGexzpqcxm"><g class="ft5dv1b6b"><path class="gr70o2bnl"/><path clip-rule="evenodd" class="nqu-0evvj"/><path class="kqeot6bhn"/></g></mask></defs><path mask="url(#SVGexzpqcxm)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:tree-duotone" {...props}></Icon>
