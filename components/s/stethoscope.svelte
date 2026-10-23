<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/m/m7b69nb6a.css';
import '../../css/z/z0wwv1b9z.css';
import '../../css/v/vot82uh-i.css';
import '../../css/g/g28iz0beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="m7b69nb6a"/><path class="z0wwv1b9z"/><path class="vot82uh-i"/><path class="g28iz0beu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:stethoscope" {...props}></Icon>
