<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mkprlx1pi.css';
import '../../css/i/id8zlgdpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mkprlx1pi"/><path class="id8zlgdpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:skype" {...props}></Icon>
