<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f7v_7vb-u.css';
import '../../css/l/ls6nhvbak.css';
import '../../css/o/o54k0kb2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f7v_7vb-u"/><path class="ls6nhvbak"/><path clip-rule="evenodd" class="o54k0kb2a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:theater-mask-flat" {...props}></Icon>
