<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mmz72pbsz.css';
import '../../css/n/nb23r6rtq.css';
import '../../css/m/mgzqwqbpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mmz72pbsz"/><path clip-rule="evenodd" class="nb23r6rtq"/><path class="mgzqwqbpj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:smart-watch-circle" {...props}></Icon>
