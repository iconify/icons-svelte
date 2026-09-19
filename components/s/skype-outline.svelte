<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnana9thp.css';
import '../../css/h/hpjr1hd0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nnana9thp"/><path clip-rule="evenodd" class="hpjr1hd0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:skype-outline" {...props}></Icon>
