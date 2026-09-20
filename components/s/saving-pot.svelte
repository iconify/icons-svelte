<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6zqz9boz.css';
import '../../css/v/v938tnbhr.css';
import '../../css/h/hlf86pbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6zqz9boz"/><path class="v938tnbhr"/><path class="hlf86pbji"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:saving-pot" {...props}></Icon>
